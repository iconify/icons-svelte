<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6wabb6_h.css';
import '../../css/z/zusfn4bvk.css';
import '../../css/o/ob8nvrsgq.css';
import '../../css/w/w_k7kvb7w.css';
import '../../css/k/kkkkd4_9x.css';
import '../../css/u/ukp8a_2li.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w6wabb6_h"/><path clip-rule="evenodd" class="zusfn4bvk"/><path clip-rule="evenodd" class="ob8nvrsgq"/><path class="w_k7kvb7w"/><path clip-rule="evenodd" class="kkkkd4_9x"/><path class="ukp8a_2li"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:hid" {...props}></Icon>
