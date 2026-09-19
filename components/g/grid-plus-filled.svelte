<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/neukm1fuz.css';
import '../../css/b/bhbvqjyxk.css';
import '../../css/k/kr2jicboj.css';
import '../../css/a/au_2_ma1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="neukm1fuz"/><rect class="bhbvqjyxk"/><rect class="kr2jicboj"/><path class="au_2_ma1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:grid-plus-filled" {...props}></Icon>
