<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tozv2lbrl.css';
import '../../css/q/qk8hpubkt.css';
import '../../css/w/w51n_2blg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tozv2lbrl"/><path class="qk8hpubkt"/><path class="w51n_2blg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:fund-twotone" {...props}></Icon>
