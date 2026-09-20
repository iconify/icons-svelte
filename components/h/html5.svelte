<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbjmc1hvx.css';
import '../../css/m/mu4g-lbau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cbjmc1hvx"/><path clip-rule="evenodd" class="mu4g-lbau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:html5" {...props}></Icon>
