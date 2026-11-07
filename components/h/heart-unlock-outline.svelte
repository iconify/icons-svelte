<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebl2e7rnn.css';
import '../../css/o/oj866ibnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ebl2e7rnn"/><path clip-rule="evenodd" class="oj866ibnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:heart-unlock-outline" {...props}></Icon>
