<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/q/qjmzsy.css';
import '../../css/c/cn_flp.css';
import '../../css/z/z1niil.css';
import '../../css/a/agm2oc.css';
import '../../css/s/so-from-18.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c qjmzsy"/><path class="a0m25c cn_flp"/><path class="a0m25c z1niil"/><path class="a0m25c agm2oc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:cloud-up" {...props}></Icon>
