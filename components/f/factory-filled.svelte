<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no1_mybjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="no1_mybjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:factory-filled" {...props}></Icon>
