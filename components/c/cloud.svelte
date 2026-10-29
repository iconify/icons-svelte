<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4dwnrrhs.css';
import '../../css/j/jvhewq0dz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n4dwnrrhs"/><path class="jvhewq0dz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:cloud" {...props}></Icon>
