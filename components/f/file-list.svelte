<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emd4_pw8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="emd4_pw8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:file-list" {...props}></Icon>
