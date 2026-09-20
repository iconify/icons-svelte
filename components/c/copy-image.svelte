<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/q/qagc1qa8v.css';
import '../../css/s/sicbtiqev.css';
import '../../css/a/a1hf6cbte.css';
import '../../css/t/ts9smabjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qagc1qa8v"/><rect class="sicbtiqev"/><circle class="a1hf6cbte"/><path class="ts9smabjq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:copy-image" {...props}></Icon>
