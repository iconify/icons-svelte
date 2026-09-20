<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3nrn22hp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q3nrn22hp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:gem-b-fill" {...props}></Icon>
