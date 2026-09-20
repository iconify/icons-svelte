<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqx4czu-u.css';
import '../../css/k/koinx6osy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eqx4czu-u"/><path class="koinx6osy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:organization-24" {...props}></Icon>
