<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k57tyqkbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k57tyqkbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:leaf-solid" {...props}></Icon>
