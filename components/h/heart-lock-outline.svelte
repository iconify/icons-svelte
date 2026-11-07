<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebl2e7rnn.css';
import '../../css/n/n84cny5hn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ebl2e7rnn"/><path clip-rule="evenodd" class="n84cny5hn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:heart-lock-outline" {...props}></Icon>
