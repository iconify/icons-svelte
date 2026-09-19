<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6gk9xwql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t6gk9xwql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:arrow-forward-thick" {...props}></Icon>
