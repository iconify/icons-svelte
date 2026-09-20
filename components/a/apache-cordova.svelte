<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p05qn7boj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p05qn7boj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:apache-cordova" {...props}></Icon>
