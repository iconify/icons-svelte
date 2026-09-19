<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5evaxbui.css';
import '../../css/b/bhbvqjyxk.css';
import '../../css/k/kr2jicboj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j5evaxbui"/><rect class="bhbvqjyxk"/><rect class="kr2jicboj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:grid-circle-diagonal-left-filled" {...props}></Icon>
