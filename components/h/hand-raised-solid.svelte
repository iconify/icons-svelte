<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bu1frrbcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bu1frrbcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:hand-raised-solid" {...props}></Icon>
