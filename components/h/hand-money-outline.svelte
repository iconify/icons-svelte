<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjsswl0up.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bjsswl0up"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hand-money-outline" {...props}></Icon>
