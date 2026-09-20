<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jv851mbmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jv851mbmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:contact-book-remix" {...props}></Icon>
