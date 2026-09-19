<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec43ctbch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ec43ctbch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-7-fill" {...props}></Icon>
