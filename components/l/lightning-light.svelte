<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivjvz2eii.css';
import '../../css/p/pkgjvccjw.css';
import '../../css/l/l7wzwbbie.css';
import '../../css/m/myrna_blh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVG60XUXchT" width="12" height="20" x="6" y="2" maskUnits="userSpaceOnUse" class="ivjvz2eii"><path class="pkgjvccjw"/><path class="l7wzwbbie"/></mask><path mask="url(#SVG60XUXchT)" class="myrna_blh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:lightning-light" {...props}></Icon>
