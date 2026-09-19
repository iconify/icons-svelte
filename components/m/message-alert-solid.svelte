<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8hy7ukcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b8hy7ukcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:message-alert-solid" {...props}></Icon>
