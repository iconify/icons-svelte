<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri4pj7yyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ri4pj7yyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:language-ruby-on-rails" {...props}></Icon>
