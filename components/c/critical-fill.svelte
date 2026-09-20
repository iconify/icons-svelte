<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhmmc_lgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qhmmc_lgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:critical-fill" {...props}></Icon>
