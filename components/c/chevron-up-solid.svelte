<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0y6itbut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t0y6itbut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:chevron-up-solid" {...props}></Icon>
