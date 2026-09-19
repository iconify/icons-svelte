<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6y9utx6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q6y9utx6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:public-speaking-filled" {...props}></Icon>
