<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uij4f5b-x.css';
import '../../css/f/f7f__c0js.css';
import '../../css/v/vjilnacka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":126,"height":31};
const content = `<g class="uij4f5b-x"><path class="f7f__c0js"/><path class="vjilnacka"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pocus" {...props}></Icon>
