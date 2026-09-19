<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4qmq9bbm.css';
import '../../css/a/anprkxbfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4qmq9bbm"/><path clip-rule="evenodd" class="anprkxbfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:adobe-photoshop-solid" {...props}></Icon>
