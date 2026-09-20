<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_jda-bzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_jda-bzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:message-square-lines-sharp" {...props}></Icon>
