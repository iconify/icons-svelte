<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfkejab2s.css';
import '../../css/c/c-nkdabpd.css';
import '../../css/i/imx8deb6i.css';
import '../../css/r/rf6rlnhzn.css';
import '../../css/d/dbdiu6u0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kfkejab2s"/><path class="c-nkdabpd"/><path class="imx8deb6i"/><path class="rf6rlnhzn"/><path class="dbdiu6u0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mistral" {...props}></Icon>
