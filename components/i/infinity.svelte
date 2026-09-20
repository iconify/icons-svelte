<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bs0y50bvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bs0y50bvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:infinity" {...props}></Icon>
