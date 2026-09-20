<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzu8y9-ki.css';
import '../../css/h/hyp6ycbyw.css';
import '../../css/q/qy525jbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="kzu8y9-ki"/><path class="hyp6ycbyw"/><path class="qy525jbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:flag-qatar" {...props}></Icon>
