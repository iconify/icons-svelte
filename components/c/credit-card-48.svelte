<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txant-bxm.css';
import '../../css/m/mc_31q86u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="txant-bxm"/><path class="mc_31q86u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:credit-card-48" {...props}></Icon>
