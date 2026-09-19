<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezyz04baj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ezyz04baj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-3-square-fill" {...props}></Icon>
