<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gul6c2bst.css';
import '../../css/l/lo5b6ob4a.css';
import '../../css/k/kmhzx59nw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGnS3rkbHK" class="gul6c2bst"/></defs><path class="lo5b6ob4a"/><use href="#SVGnS3rkbHK"/><path class="kmhzx59nw"/><use href="#SVGnS3rkbHK"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:jop" {...props}></Icon>
