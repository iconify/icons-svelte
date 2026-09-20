<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbe4v4n8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbe4v4n8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:apache-tomcat" {...props}></Icon>
