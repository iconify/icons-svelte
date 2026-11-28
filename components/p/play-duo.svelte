<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1i6nebwi.css';
import '../../css/n/nsykuxbye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o1i6nebwi secondary"/><path class="nsykuxbye primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:play-duo" {...props}></Icon>
