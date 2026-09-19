<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml-ijac5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ml-ijac5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:link-external-fill" {...props}></Icon>
