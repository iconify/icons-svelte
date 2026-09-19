<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n74bk89qt.css';
import '../../css/j/jmu1l6njj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n74bk89qt"/><path clip-rule="evenodd" class="jmu1l6njj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:clock-outline" {...props}></Icon>
