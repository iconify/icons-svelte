<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0yyv8elf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f0yyv8elf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:chat" {...props}></Icon>
