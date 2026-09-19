<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-q3jxbjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v-q3jxbjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:pointer-down-fill" {...props}></Icon>
