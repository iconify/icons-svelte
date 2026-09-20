<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wes4atb4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wes4atb4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:credit-card-check-sharp" {...props}></Icon>
