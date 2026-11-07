<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p63rntbns.css';
import '../../css/l/lkozawy4w.css';
import '../../css/w/w314yoqtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p63rntbns"/><path class="lkozawy4w"/><path clip-rule="evenodd" class="w314yoqtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:minimalistic-magnifier-check-outline" {...props}></Icon>
