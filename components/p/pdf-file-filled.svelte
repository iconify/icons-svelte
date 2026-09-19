<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8s7p28am.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t8s7p28am"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:pdf-file-filled" {...props}></Icon>
