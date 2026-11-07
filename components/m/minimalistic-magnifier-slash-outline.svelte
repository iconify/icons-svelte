<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p63rntbns.css';
import '../../css/n/n_sy2m0fq.css';
import '../../css/w/w314yoqtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p63rntbns"/><path class="n_sy2m0fq"/><path clip-rule="evenodd" class="w314yoqtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:minimalistic-magnifier-slash-outline" {...props}></Icon>
