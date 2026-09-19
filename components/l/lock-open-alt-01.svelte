<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x73g-fbxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x73g-fbxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:lock-open-alt-01" {...props}></Icon>
