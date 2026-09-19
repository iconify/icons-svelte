<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4hrb0bhl.css';
import '../../css/e/ekp95gbqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":23,"height":24};
const content = `<path class="o4hrb0bhl"/><path class="ekp95gbqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:laboratory" {...props}></Icon>
