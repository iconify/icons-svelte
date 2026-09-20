<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2-ygo_xi.css';
import '../../css/j/j3loqwvbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f2-ygo_xi"/><path class="j3loqwvbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:earpods-ear-bold" {...props}></Icon>
