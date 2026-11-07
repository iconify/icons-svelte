<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyxk3mbql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yyxk3mbql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bolt-broken" {...props}></Icon>
