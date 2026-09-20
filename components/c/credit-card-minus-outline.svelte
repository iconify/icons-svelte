<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu8rnse9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mu8rnse9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:credit-card-minus-outline" {...props}></Icon>
