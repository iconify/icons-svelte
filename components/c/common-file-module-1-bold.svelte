<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/altng4btx.css';
import '../../css/v/v7d9vybds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="altng4btx"/><path class="v7d9vybds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:common-file-module-1-bold" {...props}></Icon>
