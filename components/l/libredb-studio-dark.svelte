<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uezwkhbui.css';
import '../../css/k/k-_y3hhqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uezwkhbui"/><path class="k-_y3hhqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:libredb-studio-dark" {...props}></Icon>
