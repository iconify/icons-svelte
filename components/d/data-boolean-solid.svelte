<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh1wx-cjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eh1wx-cjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:data-boolean-solid" {...props}></Icon>
