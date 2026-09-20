<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf2h6wznc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kf2h6wznc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:github-fill-24" {...props}></Icon>
