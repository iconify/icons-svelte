<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tacaomvbw.css';
import '../../css/c/ckfmp0bvq.css';
import '../../css/y/yi7l1_bae.css';
import '../../css/b/brv_2tt_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="tacaomvbw"/><path class="ckfmp0bvq"/><path class="yi7l1_bae"/><path class="brv_2tt_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:pulumi-wordmark" {...props}></Icon>
