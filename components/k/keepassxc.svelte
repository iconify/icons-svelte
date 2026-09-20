<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7lj7fb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b7lj7fb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:keepassxc" {...props}></Icon>
