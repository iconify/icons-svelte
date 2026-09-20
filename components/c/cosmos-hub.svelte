<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9p35ebyv.css';
import '../../css/t/tn1bqmqhf.css';
import '../../css/f/fle4ekbxc.css';
import '../../css/m/m2bcqj2zn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k9p35ebyv"/><path clip-rule="evenodd" class="tn1bqmqhf"/><path class="fle4ekbxc"/><path clip-rule="evenodd" class="m2bcqj2zn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cosmos-hub" {...props}></Icon>
