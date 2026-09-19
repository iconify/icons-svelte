<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urhsqs_4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="urhsqs_4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:credit-card-alt" {...props}></Icon>
