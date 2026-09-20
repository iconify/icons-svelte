<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ty-lp-pnh.css';
import '../../css/m/mz_p1xb-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ty-lp-pnh"/><path clip-rule="evenodd" class="mz_p1xb-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:location" {...props}></Icon>
