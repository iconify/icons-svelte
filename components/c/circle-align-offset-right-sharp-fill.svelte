<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ff8cuy0tf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ff8cuy0tf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-align-offset-right-sharp-fill" {...props}></Icon>
