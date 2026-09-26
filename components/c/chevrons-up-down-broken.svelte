<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/m/md2-ubbkw.css';
import '../../css/w/wjnwtubpm.css';
import '../../css/w/w3b9nxekf.css';
import '../../css/w/w3fj3ibba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="md2-ubbkw"/><path class="wjnwtubpm"/><path class="w3b9nxekf"/><path class="w3fj3ibba"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chevrons-up-down-broken" {...props}></Icon>
