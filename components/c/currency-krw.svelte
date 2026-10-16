<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsao1jbch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gsao1jbch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:currency-krw" {...props}></Icon>
