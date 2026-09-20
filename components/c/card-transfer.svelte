<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1jvpqpaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l1jvpqpaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:card-transfer" {...props}></Icon>
