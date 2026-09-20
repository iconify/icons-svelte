<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmj_u7gyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pmj_u7gyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:credit-card-5-solid" {...props}></Icon>
