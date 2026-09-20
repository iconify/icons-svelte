<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smbn1vbdh.css';
import '../../css/g/ghwq-ivuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smbn1vbdh"/><path class="ghwq-ivuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:image-fill" {...props}></Icon>
