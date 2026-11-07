<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb-4crb9y.css';
import '../../css/g/gydy3ndrg.css';
import '../../css/r/re_l3eb8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eb-4crb9y"/><path class="gydy3ndrg"/><path clip-rule="evenodd" class="re_l3eb8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:flip-vertical-bold" {...props}></Icon>
