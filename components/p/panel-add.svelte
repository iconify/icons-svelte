<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8pydyx2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r8pydyx2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:panel-add" {...props}></Icon>
