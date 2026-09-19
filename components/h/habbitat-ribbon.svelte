<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0o9srj-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o0o9srj-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:habbitat-ribbon" {...props}></Icon>
