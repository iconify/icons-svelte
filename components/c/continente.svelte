<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovx-jb9nw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovx-jb9nw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:continente" {...props}></Icon>
