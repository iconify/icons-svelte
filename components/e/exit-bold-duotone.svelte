<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyvqlqxww.css';
import '../../css/a/axuu9gdaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cyvqlqxww"/><path clip-rule="evenodd" class="axuu9gdaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:exit-bold-duotone" {...props}></Icon>
