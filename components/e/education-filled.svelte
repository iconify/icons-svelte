<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-m7aobza.css';
import '../../css/f/fldmn0cpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b o-m7aobza"/><path class="b fldmn0cpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:education-filled" {...props}></Icon>
