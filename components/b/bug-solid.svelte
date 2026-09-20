<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7pa4eh1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v7pa4eh1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:bug-solid" {...props}></Icon>
