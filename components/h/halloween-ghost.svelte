<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo6q_ggpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eo6q_ggpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:halloween-ghost" {...props}></Icon>
