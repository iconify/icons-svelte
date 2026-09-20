<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwkxvej8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pwkxvej8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:necktie-fill" {...props}></Icon>
