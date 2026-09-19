<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/faq4sdb0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="faq4sdb0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:elm" {...props}></Icon>
