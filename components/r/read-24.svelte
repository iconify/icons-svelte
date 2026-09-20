<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krjlgs_6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="krjlgs_6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:read-24" {...props}></Icon>
