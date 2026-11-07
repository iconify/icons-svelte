<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enn3tn4xs.css';
import '../../css/w/w-oye57eg.css';
import '../../css/k/k3301qb-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="enn3tn4xs"/><path class="w-oye57eg"/><path class="k3301qb-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pen-new-square-bold" {...props}></Icon>
