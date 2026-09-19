<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbnf9-bmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbnf9-bmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:buddhism-filled" {...props}></Icon>
