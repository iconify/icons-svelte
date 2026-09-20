<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th6z7zbvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="th6z7zbvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:face-man" {...props}></Icon>
