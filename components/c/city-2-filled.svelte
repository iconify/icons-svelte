<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvy8sjoer.css';
import '../../css/b/b-nsf-bwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cvy8sjoer"/><path class="b-nsf-bwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:city-2-filled" {...props}></Icon>
