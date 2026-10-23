<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue82kj6gk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ue82kj6gk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:credit-card-x" {...props}></Icon>
