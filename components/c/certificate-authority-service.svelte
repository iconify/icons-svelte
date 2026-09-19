<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmf7520zx.css';
import '../../css/q/q8_kvdbel.css';
import '../../css/w/w-wb9bbqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jmf7520zx"/><path class="q8_kvdbel"/><path class="w-wb9bbqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:certificate-authority-service" {...props}></Icon>
