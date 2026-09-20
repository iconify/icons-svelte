<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofqcakjlm.css';
import '../../css/l/lr1fnhkrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ofqcakjlm"/><path class="lr1fnhkrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:billing-info" {...props}></Icon>
