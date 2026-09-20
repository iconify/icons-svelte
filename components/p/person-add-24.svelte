<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7ovb7b3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w7ovb7b3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:person-add-24" {...props}></Icon>
