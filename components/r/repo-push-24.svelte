<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3aizm_py.css';
import '../../css/q/qeheuacbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k3aizm_py"/><path class="qeheuacbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:repo-push-24" {...props}></Icon>
