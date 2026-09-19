<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwyb6n-0h.css';
import '../../css/q/qo15eky2l.css';
import '../../css/f/fr80xwbvq.css';
import '../../css/y/yi3v55ama.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="lwyb6n-0h"/><circle class="qo15eky2l"/><circle class="fr80xwbvq"/><circle class="yi3v55ama"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:entropy-filled" {...props}></Icon>
