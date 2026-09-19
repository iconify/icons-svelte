<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wc4ch3rjw.css';
import '../../css/j/jczmvvbsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wc4ch3rjw"/><path class="jczmvvbsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:burger-alt" {...props}></Icon>
