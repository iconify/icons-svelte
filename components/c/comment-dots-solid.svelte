<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa6k8cc-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oa6k8cc-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:comment-dots-solid" {...props}></Icon>
