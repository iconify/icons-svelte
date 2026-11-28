<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w93ba07rq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w93ba07rq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:credit-card-plus" {...props}></Icon>
