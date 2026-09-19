<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajpy7dbzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ajpy7dbzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:fork" {...props}></Icon>
