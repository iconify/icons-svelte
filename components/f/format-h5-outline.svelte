<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ar8ztobwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:format-h5-outline" {...props}></Icon>
<style>
:global(.ar8ztobwa) {
  fill: currentColor;
  d: path("M4 16.5v-9h1v4h5v-4h1v9h-1v-4H5v4zm9 0v-1h5.385q.269 0 .442-.173t.173-.442v-1.77q0-.269-.173-.442t-.443-.173H13v-5h7v1h-6v3h4.385q.666 0 1.14.475t.475 1.14v1.77q0 .666-.475 1.14t-1.14.475z");
}

</style>
