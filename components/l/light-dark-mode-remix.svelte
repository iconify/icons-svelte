<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg5nvhb1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gg5nvhb1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:light-dark-mode-remix" {...props}></Icon>
