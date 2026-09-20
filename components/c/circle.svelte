<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7leg9b-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x7leg9b-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:circle" {...props}></Icon>
