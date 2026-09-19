<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8fc5u6ec.css';
import '../../css/i/iiydukdos.css';
import '../../css/g/g4-28t0-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-primary-layer t8fc5u6ec"/><path class="duoicon-secondary-layer iiydukdos"/><path class="duoicon-primary-layer g4-28t0-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:cloud-snow" {...props}></Icon>
