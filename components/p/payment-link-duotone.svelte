<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-yo71rqa.css';
import '../../css/o/od9ez2buj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x-yo71rqa"/><path class="od9ez2buj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:payment-link-duotone" {...props}></Icon>
