<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebl2e7rnn.css';
import '../../css/a/ae3wunbcx.css';
import '../../css/e/e67gh4ytw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ebl2e7rnn"/><path class="ae3wunbcx"/><path clip-rule="evenodd" class="e67gh4ytw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:heart-unlock-bold-duotone" {...props}></Icon>
