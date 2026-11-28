<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm5fw8qnf.css';
import '../../css/s/sd92k-bou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dm5fw8qnf secondary"/><path class="primary sd92k-bou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:number-8-duo" {...props}></Icon>
