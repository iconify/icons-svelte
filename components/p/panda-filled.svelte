<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kl-up0lit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kl-up0lit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:panda-filled" {...props}></Icon>
