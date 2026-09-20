<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn74v6bbn.css';
import '../../css/j/jjvt2sqaa.css';
import '../../css/c/cvu64vbfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nn74v6bbn"/><path class="jjvt2sqaa"/><path class="cvu64vbfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:compass-duotone" {...props}></Icon>
