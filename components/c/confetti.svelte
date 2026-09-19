<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtaspevdd.css';
import '../../css/v/v206u3j4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer rtaspevdd"/><path class="duoicon-primary-layer v206u3j4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:confetti" {...props}></Icon>
