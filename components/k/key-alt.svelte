<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/x/x8eiw_bwt.css';
import '../../css/n/nc5jv0bhh.css';
import '../../css/w/wkienvanw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><path class="x8eiw_bwt"/><circle class="nc5jv0bhh"/><path class="wkienvanw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:key-alt" {...props}></Icon>
