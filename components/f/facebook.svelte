<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyayll8ub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yyayll8ub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:facebook" {...props}></Icon>
